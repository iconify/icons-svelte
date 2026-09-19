<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbc_a30nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbc_a30nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:umbrella-fill" {...props}></Icon>
