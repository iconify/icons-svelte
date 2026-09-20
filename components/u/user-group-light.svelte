<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz9i_4cdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz9i_4cdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-group-light" {...props}></Icon>
