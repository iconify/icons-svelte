<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok2z6czne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ok2z6czne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:unlock-x" {...props}></Icon>
