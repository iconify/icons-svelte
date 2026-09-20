<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-sdg286s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v-sdg286s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:text-formatting-text-field" {...props}></Icon>
