<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz_tv8bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="oz_tv8bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:tripadvisor" {...props}></Icon>
