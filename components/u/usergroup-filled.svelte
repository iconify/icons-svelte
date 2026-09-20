<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu7_b03hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu7_b03hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:usergroup-filled" {...props}></Icon>
