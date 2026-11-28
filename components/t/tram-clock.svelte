<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2h87kb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2h87kb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tram-clock" {...props}></Icon>
