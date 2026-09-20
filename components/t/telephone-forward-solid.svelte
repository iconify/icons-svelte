<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-llmdlgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-llmdlgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:telephone-forward-solid" {...props}></Icon>
