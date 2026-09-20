<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn2zd0bek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn2zd0bek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:widget5-filled" {...props}></Icon>
