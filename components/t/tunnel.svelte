<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkpfn6bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkpfn6bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:tunnel" {...props}></Icon>
