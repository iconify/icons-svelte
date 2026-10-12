<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6b2rgrbw.css';
import '../../css/l/l5tywcbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m6b2rgrbw"/><path class="l5tywcbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shrimp-off-filled" {...props}></Icon>
