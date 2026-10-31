<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxu6oxjbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxu6oxjbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tooth-fill-round" {...props}></Icon>
