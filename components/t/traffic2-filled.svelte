<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm2q63wql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fm2q63wql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:traffic2-filled" {...props}></Icon>
