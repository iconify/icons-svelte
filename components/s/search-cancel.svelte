<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1_t7obhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n1_t7obhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:search-cancel" {...props}></Icon>
