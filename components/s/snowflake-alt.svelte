<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qibh9ubbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qibh9ubbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:snowflake-alt" {...props}></Icon>
