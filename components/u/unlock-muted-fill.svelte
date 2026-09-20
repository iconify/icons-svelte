<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2vuvdbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2vuvdbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:unlock-muted-fill" {...props}></Icon>
