<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn969ul5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kn969ul5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:trumpet-24" {...props}></Icon>
