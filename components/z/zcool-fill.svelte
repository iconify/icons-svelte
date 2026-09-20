<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi-0scbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi-0scbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:zcool-fill" {...props}></Icon>
