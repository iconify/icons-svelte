<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-c_0r8kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-c_0r8kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:speechless-filled" {...props}></Icon>
