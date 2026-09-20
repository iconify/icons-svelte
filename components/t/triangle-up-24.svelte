<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t27wpd78u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t27wpd78u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-up-24" {...props}></Icon>
