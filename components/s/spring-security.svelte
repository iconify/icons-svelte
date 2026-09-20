<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwy0d1dqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwy0d1dqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:spring-security" {...props}></Icon>
