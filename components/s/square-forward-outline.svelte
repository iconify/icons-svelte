<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn528ebyy.css';
import '../../css/i/ixa_i_r1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn528ebyy"/><path class="ixa_i_r1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-forward-outline" {...props}></Icon>
