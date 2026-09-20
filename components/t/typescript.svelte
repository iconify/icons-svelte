<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqzxv8ray.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqzxv8ray"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:typescript" {...props}></Icon>
