<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqo-8vfeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tqo-8vfeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:user-outline" {...props}></Icon>
