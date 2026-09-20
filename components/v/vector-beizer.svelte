<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xthn5fbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xthn5fbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:vector-beizer" {...props}></Icon>
