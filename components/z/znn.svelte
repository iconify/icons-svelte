<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa7jysbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa7jysbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:znn" {...props}></Icon>
