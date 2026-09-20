<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx27k-jtf.css';
import '../../css/n/ngwmr6pgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx27k-jtf"/><path class="ngwmr6pgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ttk" {...props}></Icon>
