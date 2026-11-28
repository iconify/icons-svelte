<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-_72eb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-_72eb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:settings-x" {...props}></Icon>
