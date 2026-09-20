<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmbhbh3kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmbhbh3kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:zodiac-capricorn" {...props}></Icon>
