<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfnq4gk-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfnq4gk-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shirt-filled" {...props}></Icon>
