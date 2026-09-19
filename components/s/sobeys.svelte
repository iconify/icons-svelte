<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujxxnx5nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujxxnx5nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sobeys" {...props}></Icon>
