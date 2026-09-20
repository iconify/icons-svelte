<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n81nwsbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n81nwsbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:suse" {...props}></Icon>
