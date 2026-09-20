<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t91lz3ile.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t91lz3ile"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:times-circle" {...props}></Icon>
