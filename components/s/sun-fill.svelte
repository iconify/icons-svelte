<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz6p9kmmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bz6p9kmmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:sun-fill" {...props}></Icon>
