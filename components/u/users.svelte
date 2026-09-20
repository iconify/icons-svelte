<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwhrlublz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwhrlublz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:users" {...props}></Icon>
