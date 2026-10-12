<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltayglbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ltayglbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-slash-filled" {...props}></Icon>
