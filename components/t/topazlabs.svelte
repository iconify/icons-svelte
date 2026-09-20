<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb_7r-iwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb_7r-iwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:topazlabs" {...props}></Icon>
