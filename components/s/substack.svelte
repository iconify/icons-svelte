<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fggsgq7jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fggsgq7jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:substack" {...props}></Icon>
