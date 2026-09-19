<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj1lpsbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj1lpsbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:shell-recharge" {...props}></Icon>
