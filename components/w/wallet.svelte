<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9uymhwhj.css';
import '../../css/v/veovc1s6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9uymhwhj"/><path class="veovc1s6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wallet" {...props}></Icon>
