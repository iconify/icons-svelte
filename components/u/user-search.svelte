<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msjc9q65v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msjc9q65v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:user-search" {...props}></Icon>
