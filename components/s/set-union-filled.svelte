<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5fejthdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5fejthdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:set-union-filled" {...props}></Icon>
