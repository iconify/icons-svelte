<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvc_3lbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvc_3lbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:temple" {...props}></Icon>
