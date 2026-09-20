<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgn5ezbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgn5ezbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:smartphone-solid" {...props}></Icon>
