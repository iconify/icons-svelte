<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utw4vn0zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utw4vn0zz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:save-ribbon-light" {...props}></Icon>
