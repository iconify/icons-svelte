<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sthgrmhos.css';
import '../../css/p/pcus4nb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sthgrmhos"/><path class="pcus4nb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:seth2" {...props}></Icon>
