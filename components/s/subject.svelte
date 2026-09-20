<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hje_cmbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hje_cmbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:subject" {...props}></Icon>
