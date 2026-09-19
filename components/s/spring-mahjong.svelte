<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8i2bfk9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m8i2bfk9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:spring-mahjong" {...props}></Icon>
