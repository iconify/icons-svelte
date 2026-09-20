<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3ozppt_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3ozppt_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:thumbtack" {...props}></Icon>
