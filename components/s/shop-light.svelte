<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txbt8sb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="txbt8sb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:shop-light" {...props}></Icon>
