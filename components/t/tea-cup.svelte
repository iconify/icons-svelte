<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0fzakdfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="v0fzakdfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tea-cup" {...props}></Icon>
