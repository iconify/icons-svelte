<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drq0v9xaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drq0v9xaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:user-exclamation" {...props}></Icon>
