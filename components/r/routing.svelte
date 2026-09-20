<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8f-7w9qv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v8f-7w9qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:routing" {...props}></Icon>
