<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b526akbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b526akbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:send-alt-02" {...props}></Icon>
