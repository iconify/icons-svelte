<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6gf_ppof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="q6gf_ppof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-arrow-right" {...props}></Icon>
