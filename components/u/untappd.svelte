<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-o4zdboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-o4zdboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:untappd" {...props}></Icon>
