<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odg1w-btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="odg1w-btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:suse" {...props}></Icon>
