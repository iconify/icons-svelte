<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks9itzb5x.css';
import '../../css/a/av07jwwcc.css';
import '../../css/e/edp79wbbi.css';
import '../../css/n/n-ppa3b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks9itzb5x"/><path class="av07jwwcc"/><path class="edp79wbbi"/><path class="n-ppa3b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:unlink-bold" {...props}></Icon>
