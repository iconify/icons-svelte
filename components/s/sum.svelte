<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi58lbbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi58lbbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sum" {...props}></Icon>
