<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0mgmxb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c0mgmxb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shirt-solid" {...props}></Icon>
