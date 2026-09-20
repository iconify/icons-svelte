<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzjpmdbit.css';
import '../../css/h/h0kgu1k_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzjpmdbit"/><path class="h0kgu1k_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:uw3s" {...props}></Icon>
