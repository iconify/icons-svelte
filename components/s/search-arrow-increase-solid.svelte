<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqb9vbtsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gqb9vbtsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:search-arrow-increase-solid" {...props}></Icon>
