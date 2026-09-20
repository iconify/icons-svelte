<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lizqbob8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lizqbob8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:vip-fill" {...props}></Icon>
