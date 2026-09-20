<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sslt314qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sslt314qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:support" {...props}></Icon>
