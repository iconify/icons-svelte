<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly552tb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly552tb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:zz" {...props}></Icon>
