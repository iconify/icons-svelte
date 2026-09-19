<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejan3lbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejan3lbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:soundcloud-fill" {...props}></Icon>
