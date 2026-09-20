<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwuagw5pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwuagw5pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:scrutinizer-ci" {...props}></Icon>
