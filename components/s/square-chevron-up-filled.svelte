<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ena9jqbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ena9jqbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-chevron-up-filled" {...props}></Icon>
