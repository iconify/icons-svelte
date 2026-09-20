<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmwe6k33i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nmwe6k33i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shrimp-solid" {...props}></Icon>
