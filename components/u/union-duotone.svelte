<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_e3yyfss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary w_e3yyfss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:union-duotone" {...props}></Icon>
