<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehs5ddlli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehs5ddlli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:waterfall-light" {...props}></Icon>
