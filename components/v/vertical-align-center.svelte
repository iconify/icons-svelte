<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh-_msqeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh-_msqeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:vertical-align-center" {...props}></Icon>
