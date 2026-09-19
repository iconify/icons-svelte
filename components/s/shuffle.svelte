<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugyrw2brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugyrw2brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shuffle" {...props}></Icon>
