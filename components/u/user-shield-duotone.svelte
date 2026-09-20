<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esg-30b0c.css';
import '../../css/e/e6yhmq1dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esg-30b0c"/><path class="e6yhmq1dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-shield-duotone" {...props}></Icon>
