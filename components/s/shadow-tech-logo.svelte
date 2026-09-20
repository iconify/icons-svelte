<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqo_owmxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqo_owmxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:shadow-tech-logo" {...props}></Icon>
