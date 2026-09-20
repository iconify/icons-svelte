<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku2vqqbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku2vqqbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:weread" {...props}></Icon>
