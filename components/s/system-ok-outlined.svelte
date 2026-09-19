<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giek2mg0i.css';
import '../../css/g/gw53p_brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="giek2mg0i"/><path class="gw53p_brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:system-ok-outlined" {...props}></Icon>
