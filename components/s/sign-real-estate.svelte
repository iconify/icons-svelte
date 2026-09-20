<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5hh26bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5hh26bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sign-real-estate" {...props}></Icon>
