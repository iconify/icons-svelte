<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-x41qbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v-x41qbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wrench-duotone" {...props}></Icon>
