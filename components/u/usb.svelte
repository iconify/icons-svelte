<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmlps6b0t.css';
import '../../css/w/wt0pcikiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmlps6b0t"/><path class="wt0pcikiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:usb" {...props}></Icon>
