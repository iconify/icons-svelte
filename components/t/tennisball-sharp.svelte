<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljrzvsbti.css';
import '../../css/o/ohubqmb2c.css';
import '../../css/x/xcd4ndbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ljrzvsbti"/><path class="ohubqmb2c"/><path class="xcd4ndbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:tennisball-sharp" {...props}></Icon>
