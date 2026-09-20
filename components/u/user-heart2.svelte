<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzmp4vbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bzmp4vbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-heart2" {...props}></Icon>
