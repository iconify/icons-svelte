<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6hh-ywzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6hh-ywzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wikisource" {...props}></Icon>
