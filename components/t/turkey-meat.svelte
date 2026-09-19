<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crm-twbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crm-twbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:turkey-meat" {...props}></Icon>
