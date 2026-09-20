<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo664i1hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo664i1hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:vector-square-alt" {...props}></Icon>
