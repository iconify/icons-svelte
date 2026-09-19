<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya5a489_p.css';
import '../../css/m/md0kk7b9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya5a489_p"/><path class="md0kk7b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:waka-kotahi" {...props}></Icon>
