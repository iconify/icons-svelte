<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4sa6obug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4sa6obug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:shield-plus" {...props}></Icon>
