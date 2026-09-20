<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4n86ab4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4n86ab4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:scooter-3" {...props}></Icon>
