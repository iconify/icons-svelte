<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oprlnbclx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oprlnbclx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:yelp" {...props}></Icon>
