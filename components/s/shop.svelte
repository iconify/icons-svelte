<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shshedbqf.css';
import '../../css/o/og1rmsw3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shshedbqf"/><path clip-rule="evenodd" class="og1rmsw3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:shop" {...props}></Icon>
