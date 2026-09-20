<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdmi5-b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fdmi5-b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:turkish-lira" {...props}></Icon>
