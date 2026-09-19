<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_jmlxnvx.css';
import '../../css/m/mza_fjbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer s_jmlxnvx"/><path class="duoicon-secondary-layer mza_fjbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:user" {...props}></Icon>
