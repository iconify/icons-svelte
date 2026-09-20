<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9993z9uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9993z9uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:twitter" {...props}></Icon>
