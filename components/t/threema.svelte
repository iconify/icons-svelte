<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cou1a1nam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cou1a1nam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:threema" {...props}></Icon>
