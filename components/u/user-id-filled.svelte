<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y66n86cjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y66n86cjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-id-filled" {...props}></Icon>
