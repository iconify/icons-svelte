<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm4qedcib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fm4qedcib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:socket" {...props}></Icon>
