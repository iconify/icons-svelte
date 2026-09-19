<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w697-jb9w.css';
import '../../css/o/occ68iv3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w697-jb9w"/><path class="occ68iv3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sidebar" {...props}></Icon>
