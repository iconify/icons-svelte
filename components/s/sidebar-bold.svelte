<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzmx73baa.css';
import '../../css/j/jt5nlubqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzmx73baa"/><path clip-rule="evenodd" class="jt5nlubqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sidebar-bold" {...props}></Icon>
