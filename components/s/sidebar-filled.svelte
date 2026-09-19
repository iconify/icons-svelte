<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajhn5acdw.css';
import '../../css/o/occ68iv3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajhn5acdw"/><path class="occ68iv3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sidebar-filled" {...props}></Icon>
