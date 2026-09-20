<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a57lufbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a57lufbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yandex" {...props}></Icon>
