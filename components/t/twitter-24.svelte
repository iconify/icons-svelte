<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhrvvac2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhrvvac2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:twitter-24" {...props}></Icon>
