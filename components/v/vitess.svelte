<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dchv7qbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dchv7qbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:vitess" {...props}></Icon>
