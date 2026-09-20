<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p86ndqb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="p86ndqb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:thumbs-up" {...props}></Icon>
