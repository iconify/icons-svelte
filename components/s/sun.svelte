<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojke0rlcu.css';
import '../../css/o/ocbn0jbob.css';
import '../../css/v/vggz4i0-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer ojke0rlcu"/><path class="duoicon-secondary-layer ocbn0jbob"/><path class="duoicon-primary-layer vggz4i0-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:sun" {...props}></Icon>
