<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9y477w0i.css';
import '../../css/o/ov-0mlbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="n9y477w0i"/><path class="ov-0mlbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-bold-duotone" {...props}></Icon>
