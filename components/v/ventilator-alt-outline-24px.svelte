<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-k06jxyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-k06jxyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ventilator-alt-outline-24px" {...props}></Icon>
