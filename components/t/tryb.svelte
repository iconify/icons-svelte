<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkqqq9htt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkqqq9htt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tryb" {...props}></Icon>
