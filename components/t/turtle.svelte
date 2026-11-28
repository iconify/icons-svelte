<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as8xp1bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as8xp1bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:turtle" {...props}></Icon>
