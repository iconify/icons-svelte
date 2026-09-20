<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqq5v3bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqq5v3bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:sonarqube-for-ide" {...props}></Icon>
