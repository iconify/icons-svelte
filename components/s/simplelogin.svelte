<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5u5tib_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5u5tib_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:simplelogin" {...props}></Icon>
